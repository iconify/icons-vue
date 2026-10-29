<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sf9w4fbdp.css';
import '../../css/k/kx1xlobhp.css';
import '../../css/t/tf-bdq1-t.css';
import '../../css/x/xlofp7gdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sf9w4fbdp"/><path class="kx1xlobhp wm-a"/><path class="tf-bdq1-t wm-k"/><path class="wm-a xlofp7gdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:laddoo-sketch" /></template>
