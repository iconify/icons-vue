<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ibs3thi1n.css';
import '../../css/q/qz9sq0bxe.css';
import '../../css/b/bhka77qrs.css';
import '../../css/d/dvj8nwb_d.css';
import '../../css/p/ppbtr7vum.css';
import '../../css/h/h_tsn8bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ibs3thi1n"/><path class="qz9sq0bxe"/><path class="bhka77qrs"/><path class="dvj8nwb_d"/><path class="ppbtr7vum"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-scan-line-duotone" /></template>
