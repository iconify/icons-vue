<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/arzno-wyz.css';
import '../../css/o/o_taswthd.css';
import '../../css/c/cwc236bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="arzno-wyz"/><path class="o_taswthd"/><path class="cwc236bjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-line-duotone" /></template>
