<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0rquab4m.css';
import '../../css/c/cxnnz0b1p.css';
import '../../css/s/s353xd64o.css';
import '../../css/z/z-itscb-x.css';
import '../../css/c/crgxpcbmq.css';
import '../../css/h/hr6_0tnzh.css';
import '../../css/r/r-mdnlbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0rquab4m"/><path class="cxnnz0b1p"/><path class="s353xd64o"/><circle class="z-itscb-x"/><circle class="crgxpcbmq"/><path class="hr6_0tnzh"/><ellipse class="r-mdnlbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:camera" /></template>
