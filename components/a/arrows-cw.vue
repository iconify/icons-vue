<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2sryobdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":857,"height":1000};
const content = `<path class="u2sryobdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:arrows-cw" /></template>
