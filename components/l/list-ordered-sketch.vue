<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z4j7jcj9k.css';
import '../../css/h/hnu19jo4s.css';
import '../../css/a/aznn2_bak.css';
import '../../css/x/x0_7tpbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z4j7jcj9k"/><path class="hnu19jo4s wm-a"/><path class="aznn2_bak wm-k"/><path class="wm-a x0_7tpbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-ordered-sketch" /></template>
