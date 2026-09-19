<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/q/qe6ha-ylc.css';
import '../../css/c/czf_y_qzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><path class="qe6ha-ylc"/><path class="czf_y_qzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:flash-payment" /></template>
