<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c-z4wj6nw.css';
import '../../css/f/fozni9buu.css';
import '../../css/z/zxdihacgb.css';
import '../../css/n/n-07r-b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c-z4wj6nw wm-k"/><path class="fozni9buu wm-shadow"/><path class="wm-k zxdihacgb"/><path class="n-07r-b5s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flask-conical-engrave" /></template>
