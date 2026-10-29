<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/usuo7wblk.css';
import '../../css/o/oj2nrac_h.css';
import '../../css/e/e-e-cxbmn.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/k/k3tex3kws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="usuo7wblk wm-k"/><path class="oj2nrac_h wm-a"/><path class="e-e-cxbmn wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="k3tex3kws wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baseball-engrave" /></template>
