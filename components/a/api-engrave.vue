<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/ko7dz5wwb.css';
import '../../css/l/l102dbhsr.css';
import '../../css/b/bykglcbce.css';
import '../../css/v/v86i0g9gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ko7dz5wwb wm-k"/><path class="l102dbhsr wm-shadow"/><path class="bykglcbce wm-k"/><path class="v86i0g9gf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:api-engrave" /></template>
