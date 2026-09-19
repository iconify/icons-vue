<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/u42z6638m.css';
import '../../css/z/zy_ves9iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><rect class="u42z6638m"/><path class="zy_ves9iz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-double-stroke-12" /></template>
