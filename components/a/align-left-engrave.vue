<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ejopvybvf.css';
import '../../css/n/n-xoksf_a.css';
import '../../css/k/k6v14padp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ejopvybvf"/><path class="n-xoksf_a wm-shadow"/><path class="k6v14padp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-left-engrave" /></template>
