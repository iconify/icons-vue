<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bvupyobzo.css';
import '../../css/u/uqb8hz1bt.css';
import '../../css/k/kewz__byf.css';
import '../../css/a/a6ey7sbng.css';
import '../../css/r/rvvxdgw4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bvupyobzo wm-k"/><path class="uqb8hz1bt wm-a"/><path class="kewz__byf wm-shadow"/><path class="a6ey7sbng wm-k"/><path class="rvvxdgw4h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:face-mask-engrave" /></template>
