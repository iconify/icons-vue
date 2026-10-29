<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dhopsub9e.css';
import '../../css/d/dk_ez364w.css';
import '../../css/a/awkb7aczt.css';
import '../../css/o/onnvrjbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dhopsub9e"/><path class="dk_ez364w wm-a"/><path class="awkb7aczt wm-k"/><path class="onnvrjbep wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-robot-sketch" /></template>
