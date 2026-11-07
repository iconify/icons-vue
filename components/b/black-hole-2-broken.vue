<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/y/yaa3skbyc.css';
import '../../css/k/kgb3mbbsa.css';
import '../../css/t/ta4khdrwc.css';
import '../../css/z/zgyerrblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><path class="yaa3skbyc"/><path class="kgb3mbbsa"/><path class="ta4khdrwc"/><path class="zgyerrblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-2-broken" /></template>
