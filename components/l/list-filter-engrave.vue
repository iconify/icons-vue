<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bi-h1cbhh.css';
import '../../css/m/ms02r72gm.css';
import '../../css/m/m9ll0eb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bi-h1cbhh"/><path class="ms02r72gm wm-shadow"/><path class="m9ll0eb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-filter-engrave" /></template>
