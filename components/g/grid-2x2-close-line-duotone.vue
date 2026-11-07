<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tb-reab7h.css';
import '../../css/d/duo8u5b0b.css';
import '../../css/d/dpswkyzrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tb-reab7h"/><path class="duo8u5b0b"/><path class="dpswkyzrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-close-line-duotone" /></template>
