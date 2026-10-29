<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qxi7yn2rl.css';
import '../../css/n/n8q0-sbxu.css';
import '../../css/m/me3qcxbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qxi7yn2rl"/><path class="n8q0-sbxu wm-shadow"/><path class="me3qcxbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bookmark-engrave" /></template>
