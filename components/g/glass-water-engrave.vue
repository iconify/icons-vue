<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x27i95usk.css';
import '../../css/l/l1h02sb3a.css';
import '../../css/m/myh2jmy5u.css';
import '../../css/e/em4t9mizl.css';
import '../../css/s/s2uhgxbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x27i95usk"/><path class="l1h02sb3a wm-a"/><path class="myh2jmy5u wm-shadow"/><path class="em4t9mizl wm-k"/><path class="s2uhgxbuo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glass-water-engrave" /></template>
