<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gi7xtcbkc.css';
import '../../css/q/qiya7tpcc.css';
import '../../css/i/ipmhgebmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gi7xtcbkc"/><path class="qiya7tpcc"/><path class="ipmhgebmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-figma" /></template>
