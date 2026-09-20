<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w0tbizb6v.css';
import '../../css/u/uq1a7euhz.css';
import '../../css/k/k5ha-2b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w0tbizb6v"/><path class="uq1a7euhz"/><path clip-rule="evenodd" class="k5ha-2b_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-sharp-duotone" /></template>
