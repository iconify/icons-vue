<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/d4l60oblr.css';
import '../../css/u/uf8-wnb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="d4l60oblr"/><circle class="uf8-wnb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-circle-stroke-12" /></template>
