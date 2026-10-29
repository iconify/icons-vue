<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hmp16njeg.css';
import '../../css/f/f78e21b0t.css';
import '../../css/j/j3l-vfqkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hmp16njeg"/><path class="f78e21b0t wm-a"/><path class="j3l-vfqkm wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clock-alert" /></template>
