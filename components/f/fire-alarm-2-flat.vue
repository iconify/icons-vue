<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hlo1_gb6y.css';
import '../../css/m/mgbv4jbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="hlo1_gb6y"/><path clip-rule="evenodd" class="mgbv4jbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:fire-alarm-2-flat" /></template>
