<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dufl35bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<g transform="translate(0 1792) scale(1 -1)"><path class="dufl35bfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-o-down" /></template>
