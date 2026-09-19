<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/k4gukjrlv.css';
import '../../css/a/a5zg-ob-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="k4gukjrlv"/><rect class="a5zg-ob-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-unlocked-stroke-16" /></template>
