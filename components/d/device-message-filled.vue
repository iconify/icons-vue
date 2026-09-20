<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/th240zbjx.css';
import '../../css/l/ll2wlbm4o.css';
import '../../css/p/p501uebdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="th240zbjx"/><path class="ll2wlbm4o"/><path class="p501uebdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:device-message-filled" /></template>
