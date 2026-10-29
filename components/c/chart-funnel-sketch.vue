<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qf3oh9fzo.css';
import '../../css/k/k138lobuf.css';
import '../../css/g/g0edfytvp.css';
import '../../css/b/b_cca24xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qf3oh9fzo wm-deco"/><path class="k138lobuf wm-k"/><path class="g0edfytvp wm-k"/><path class="b_cca24xi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-sketch" /></template>
