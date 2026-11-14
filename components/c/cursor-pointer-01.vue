<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q4c5dl-uv.css';
import '../../css/b/bpuyxlb4i.css';
import '../../css/k/k2rgfbi6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q4c5dl-uv"/><path class="bpuyxlb4i"/><path class="k2rgfbi6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-pointer-01" /></template>
