<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x1-2cibzr.css';
import '../../css/v/vh6i4x6ao.css';
import '../../css/x/xdhq8bcck.css';
import '../../css/d/da5brdyvj.css';
import '../../css/s/snvrewbju.css';
import '../../css/c/c4ppv22xk.css';
import '../../css/o/ohwwvwbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x1-2cibzr"/><path class="vh6i4x6ao wm-a"/><path class="wm-s xdhq8bcck"/><path class="da5brdyvj wm-shadow"/><path class="snvrewbju wm-k"/><path class="c4ppv22xk wm-a"/><path class="ohwwvwbof wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-dot-engrave" /></template>
