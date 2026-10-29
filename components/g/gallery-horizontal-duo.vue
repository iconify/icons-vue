<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kw9g0zbgq.css';
import '../../css/o/od38u2bjg.css';
import '../../css/o/omtqkcbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kw9g0zbgq"/><path class="od38u2bjg wm-a"/><path class="omtqkcbfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gallery-horizontal-duo" /></template>
