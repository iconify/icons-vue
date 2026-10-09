<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7o1r-80a.css';
import '../../css/a/ah0ch-vyf.css';
import '../../css/q/q_yh57bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e7o1r-80a"/><path class="ah0ch-vyf"/><path class="q_yh57bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:demand-response-20" /></template>
