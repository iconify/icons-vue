<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pu8xpsbae.css';
import '../../css/w/w9umqkvzs.css';
import '../../css/x/xk4e-oxlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pu8xpsbae"/><path class="w9umqkvzs"/><path class="xk4e-oxlk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-dashboard-duotone" /></template>
