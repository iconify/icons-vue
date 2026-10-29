<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tdtvpgh7u.css';
import '../../css/a/afw6fsbkl.css';
import '../../css/g/gcc_iacbm.css';
import '../../css/d/d7j47q-dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tdtvpgh7u"/><path class="afw6fsbkl wm-a"/><path class="gcc_iacbm wm-a"/><path class="d7j47q-dh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-pie-duo" /></template>
