<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/e/ey92g6b7j.css';
import '../../css/k/k23tj10xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="pr52f_b5y"><path class="ey92g6b7j"/><path class="k23tj10xr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:hash-print" /></template>
