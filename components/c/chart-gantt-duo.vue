<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/ce3j81iyt.css';
import '../../css/x/x4oh7ob3p.css';
import '../../css/i/iqg85keyw.css';
import '../../css/b/b67d4zo8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ce3j81iyt wm-a"/><path class="wm-a x4oh7ob3p"/><path class="iqg85keyw"/><path class="b67d4zo8u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-gantt-duo" /></template>
