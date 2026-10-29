<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spin9_bwp.css';
import '../../css/y/yxesn464s.css';
import '../../css/f/fcx47xikt.css';
import '../../css/l/lqw4xwbkq.css';
import '../../css/o/otcq8cr0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spin9_bwp"/><path class="wm-k yxesn464s"/><path class="fcx47xikt wm-a"/><path class="lqw4xwbkq wm-k"/><path class="otcq8cr0s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crown-sketch" /></template>
