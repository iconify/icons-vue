<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fi0_0_bdg.css';
import '../../css/x/xkndeybay.css';
import '../../css/o/o_a2_tbyl.css';
import '../../css/s/sxlwlmkmh.css';
import '../../css/a/a7il49b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fi0_0_bdg wm-k"/><path class="wm-a xkndeybay"/><path class="o_a2_tbyl wm-shadow"/><path class="sxlwlmkmh wm-k"/><path class="a7il49b7h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-right-engrave" /></template>
