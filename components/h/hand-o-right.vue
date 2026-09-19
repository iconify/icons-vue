<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn38qzb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<g transform="translate(1792 0) scale(-1 1)"><path class="mn38qzb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-o-right" /></template>
