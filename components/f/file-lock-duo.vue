<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c3b96qjhw.css';
import '../../css/m/my13ikbwl.css';
import '../../css/v/vp3_m3b5w.css';
import '../../css/n/ngtu3eb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c3b96qjhw"/><path class="my13ikbwl wm-a"/><path class="vp3_m3b5w"/><path class="ngtu3eb5m wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-lock-duo" /></template>
