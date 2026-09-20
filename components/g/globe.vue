<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/s/s_vlueboz.css';
import '../../css/q/qkp03cbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="hwsal5q-o"/><ellipse class="s_vlueboz"/><path class="qkp03cbde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:globe" /></template>
