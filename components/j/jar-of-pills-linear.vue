<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fs3c2u4vr.css';
import '../../css/s/smcsc6bgv.css';
import '../../css/i/iyts3fg-w.css';
import '../../css/e/ezwihtbnk.css';
import '../../css/n/nmr5z_b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fs3c2u4vr"/><path class="smcsc6bgv"/><path class="iyts3fg-w"/><path class="ezwihtbnk"/><path class="nmr5z_b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jar-of-pills-linear" /></template>
