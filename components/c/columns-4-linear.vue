<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ojv2i-bxi.css';
import '../../css/e/eyrtj4wgt.css';
import '../../css/f/f_1b_5fjb.css';
import '../../css/r/rma5_ql1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ojv2i-bxi"/><path class="eyrtj4wgt"/><path class="f_1b_5fjb"/><path class="rma5_ql1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-linear" /></template>
