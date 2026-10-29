<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f-yvlbbar.css';
import '../../css/y/ykoe54boh.css';
import '../../css/e/ef6ao3b0m.css';
import '../../css/i/is6r9tbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f-yvlbbar wm-k"/><path class="wm-a ykoe54boh"/><path class="ef6ao3b0m wm-k"/><path class="is6r9tbwq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-spline-sketch" /></template>
