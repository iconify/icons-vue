<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wr9dlac0u.css';
import '../../css/q/qb5ipy-9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":201,"height":201};
const content = `<g class="ft5dv1b6b"><path class="wr9dlac0u"/><path clip-rule="evenodd" class="qb5ipy-9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:binance" /></template>
