<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3x45msta.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m0ucqz9kr.css';
import '../../css/e/emdpkhv1c.css';
import '../../css/r/rqhxtipmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3x45msta secondary"/><g class="dt0cm9dhy primary"><path class="m0ucqz9kr"/><path class="emdpkhv1c"/><path class="rqhxtipmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-sparkles-duo" /></template>
