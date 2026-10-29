<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uq9xj6cez.css';
import '../../css/d/dlpg85fto.css';
import '../../css/h/hb98s3yxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uq9xj6cez"/><path class="dlpg85fto wm-shadow"/><path class="hb98s3yxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-up-engrave" /></template>
