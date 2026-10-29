<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d7uszhbcj.css';
import '../../css/f/flbsvpbyj.css';
import '../../css/d/dakzdk03i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d7uszhbcj"/><path class="flbsvpbyj wm-a"/><path class="dakzdk03i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-duo" /></template>
