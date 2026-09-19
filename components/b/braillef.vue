<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohra-gfaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="ohra-gfaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillef" /></template>
