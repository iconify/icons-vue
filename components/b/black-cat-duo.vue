<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lbnt75byn.css';
import '../../css/w/w27peibbj.css';
import '../../css/s/scgb-sjtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lbnt75byn"/><path class="w27peibbj wm-a"/><path class="scgb-sjtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:black-cat-duo" /></template>
