<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3ugfqabr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ou8cchb0s.css';
import '../../css/r/rqhxtipmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ugfqabr secondary"/><g class="dt0cm9dhy primary"><path class="ou8cchb0s"/><path class="rqhxtipmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-duo" /></template>
