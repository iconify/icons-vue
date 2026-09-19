<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/olkw-5b-j.css';
import '../../css/q/qhjzwr93d.css';
import '../../css/z/zeamq4byn.css';
import '../../css/s/shom5xbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="olkw-5b-j"/><path class="qhjzwr93d"/><path class="zeamq4byn"/><path class="shom5xbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-pie-slice-duo" /></template>
