<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z31n7sf4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1600};
const content = `<g transform="translate(1472 0) scale(-1 1)"><path class="z31n7sf4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-right" /></template>
