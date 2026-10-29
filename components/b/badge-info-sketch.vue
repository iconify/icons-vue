<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jzg8wibto.css';
import '../../css/n/nicx5qbaa.css';
import '../../css/g/gsir-ngtt.css';
import '../../css/m/mza_43bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jzg8wibto"/><path class="nicx5qbaa wm-a"/><path class="gsir-ngtt wm-k"/><path class="mza_43bcq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-info-sketch" /></template>
