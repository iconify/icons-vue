<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/arzno-wyz.css';
import '../../css/x/xk1mui9dn.css';
import '../../css/t/tgsr-hz9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="arzno-wyz"/><path class="xk1mui9dn"/><path class="tgsr-hz9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-linear" /></template>
