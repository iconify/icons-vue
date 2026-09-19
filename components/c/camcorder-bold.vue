<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nxsbg2x6k.css';
import '../../css/c/cobwtfbfx.css';
import '../../css/k/k-6yl9e2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><rect class="nxsbg2x6k"/><path clip-rule="evenodd" class="cobwtfbfx"/><path class="k-6yl9e2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:camcorder-bold" /></template>
