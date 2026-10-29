<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y95393_dl.css';
import '../../css/w/wci8o2bvn.css';
import '../../css/d/dx8clgbog.css';
import '../../css/y/ydg910bfg.css';
import '../../css/r/rnsc04beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="y95393_dl"/><path class="wci8o2bvn"/><path class="dx8clgbog wm-a"/><path class="wm-s ydg910bfg"/><path class="rnsc04beb wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-backup" /></template>
