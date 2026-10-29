<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yhos5ubjh.css';
import '../../css/g/gg7k0m7bl.css';
import '../../css/t/ti3m8jkqo.css';
import '../../css/x/xstlfobii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yhos5ubjh"/><path class="gg7k0m7bl wm-a"/><path class="ti3m8jkqo wm-k"/><path class="wm-a xstlfobii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-right-to-line-sketch" /></template>
