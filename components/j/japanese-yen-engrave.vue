<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m7basdqha.css';
import '../../css/y/yvyzj29rj.css';
import '../../css/o/opu4f6b7x.css';
import '../../css/m/m28cpcovm.css';
import '../../css/o/oceiybcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m7basdqha wm-k"/><path class="wm-a yvyzj29rj"/><path class="opu4f6b7x wm-shadow"/><path class="m28cpcovm wm-k"/><path class="oceiybcet wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:japanese-yen-engrave" /></template>
