<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uoqh7ofly.css';
import '../../css/f/fwrdtm7of.css';
import '../../css/x/x1dfjybuh.css';
import '../../css/o/oq5cfub0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uoqh7ofly wm-k"/><path class="fwrdtm7of wm-k"/><path class="wm-a x1dfjybuh"/><path class="oq5cfub0i wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chinese-knot-sketch" /></template>
