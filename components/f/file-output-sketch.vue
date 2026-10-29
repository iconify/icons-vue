<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kp535ebhi.css';
import '../../css/o/o66bphb6w.css';
import '../../css/u/ujl90vbzw.css';
import '../../css/f/f0635tb8o.css';
import '../../css/c/ch_u0xaan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kp535ebhi"/><path class="o66bphb6w wm-k"/><path class="ujl90vbzw wm-a"/><path class="f0635tb8o wm-k"/><path class="ch_u0xaan wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-output-sketch" /></template>
