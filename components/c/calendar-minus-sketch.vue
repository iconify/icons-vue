<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dkzxnqbrb.css';
import '../../css/r/rn54dybwb.css';
import '../../css/k/kqufevifz.css';
import '../../css/m/m6ykkbbfn.css';
import '../../css/t/tp61zgbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dkzxnqbrb"/><path class="rn54dybwb wm-k"/><path class="kqufevifz wm-a"/><path class="m6ykkbbfn wm-k"/><path class="tp61zgbyw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-minus-sketch" /></template>
