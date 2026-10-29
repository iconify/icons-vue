<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jm-h8ebfd.css';
import '../../css/f/fzlatcc_e.css';
import '../../css/t/t048yihdc.css';
import '../../css/l/lap-h8eft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jm-h8ebfd"/><path class="fzlatcc_e wm-a"/><path class="t048yihdc"/><path class="lap-h8eft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:door-open-duo" /></template>
