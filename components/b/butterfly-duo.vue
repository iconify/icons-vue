<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qxlw74g3e.css';
import '../../css/g/gpwovhbpc.css';
import '../../css/q/q56y233js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qxlw74g3e"/><path class="gpwovhbpc wm-a"/><path class="q56y233js"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:butterfly-duo" /></template>
