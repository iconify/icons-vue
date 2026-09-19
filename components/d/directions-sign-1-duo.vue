<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1bbndrsh.css';
import '../../css/s/ss_zm4agc.css';
import '../../css/f/fxze2ybkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="ss_zm4agc"/><path class="fxze2ybkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:directions-sign-1-duo" /></template>
