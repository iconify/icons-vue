<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz_kbtsof.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wbizk1a7x.css';
import '../../css/i/ip79ax0mg.css';
import '../../css/l/lwawacbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz_kbtsof secondary"/><g class="dt0cm9dhy primary"><path class="wbizk1a7x"/><path class="ip79ax0mg"/><path class="lwawacbpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:garage-duo" /></template>
