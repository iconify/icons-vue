<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kf25jz3yp.css';
import '../../css/v/vbukufbqb.css';
import '../../css/c/c-15_29zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kf25jz3yp"/><path class="vbukufbqb wm-k"/><path class="c-15_29zx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:headphones-sketch" /></template>
