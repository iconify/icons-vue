<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bu3_l_blx.css';
import '../../css/b/b058v_bim.css';
import '../../css/p/psuc-s3be.css';
import '../../css/f/fjwd2bbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bu3_l_blx"/><path class="b058v_bim wm-a"/><path class="psuc-s3be"/><path class="fjwd2bbvb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crayon-duo" /></template>
