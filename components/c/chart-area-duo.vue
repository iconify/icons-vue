<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x4sptsbot.css';
import '../../css/c/cw36_6mco.css';
import '../../css/g/gzms0bb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x4sptsbot"/><path class="cw36_6mco wm-a"/><path class="gzms0bb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-area-duo" /></template>
