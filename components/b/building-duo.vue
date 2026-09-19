<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xbl52hexa.css';
import '../../css/u/uf15v2ukv.css';
import '../../css/k/k4z577z4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xbl52hexa"/><path class="uf15v2ukv"/><path class="k4z577z4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-duo" /></template>
