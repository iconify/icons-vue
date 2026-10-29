<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gqkt7bcvk.css';
import '../../css/u/up3pyu-he.css';
import '../../css/l/ldia-8bfr.css';
import '../../css/j/js83bcb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gqkt7bcvk"/><path class="up3pyu-he wm-a"/><path class="ldia-8bfr wm-k"/><path class="js83bcb_r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:football-sketch" /></template>
