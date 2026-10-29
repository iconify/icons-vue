<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qiyypgbtt.css';
import '../../css/s/swv5gibmp.css';
import '../../css/w/wer_ogb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qiyypgbtt"/><path class="swv5gibmp wm-a"/><path class="wer_ogb9b wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-gift" /></template>
