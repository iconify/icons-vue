<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0x409cvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="u0x409cvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:black-tie" /></template>
