<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e7v762dhy.css';
import '../../css/g/gs_dhun0e.css';
import '../../css/n/nob2a0bbf.css';
import '../../css/j/j4pir7mhg.css';
import '../../css/w/wftdd0ccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e7v762dhy"/><path class="gs_dhun0e wm-shadow"/><path class="nob2a0bbf"/><path class="j4pir7mhg"/><path class="wftdd0ccr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-unicorn-engrave" /></template>
