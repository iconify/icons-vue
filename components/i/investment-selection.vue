<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/h/hh9-_ie0d.css';
import '../../css/h/hc5pfcrmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="pr52f_b5y"><path class="hh9-_ie0d"/><path class="hc5pfcrmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:investment-selection" /></template>
