<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbv_ayoio.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xhu3adbgv.css';
import '../../css/o/olf6d1bcx.css';
import '../../css/r/r3k9t2gzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbv_ayoio secondary"/><g class="dt0cm9dhy primary"><path class="xhu3adbgv"/><path class="olf6d1bcx"/><path class="r3k9t2gzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bathtub-duo" /></template>
