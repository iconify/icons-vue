<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gt80c_bza.css';
import '../../css/j/jmkpfkytf.css';
import '../../css/w/wr5q1e3do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gt80c_bza"/><path class="jmkpfkytf"/><path class="wr5q1e3do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crosshairs-slash-filled" /></template>
