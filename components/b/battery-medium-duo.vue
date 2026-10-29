<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hh6tl_orr.css';
import '../../css/n/nclc15bex.css';
import '../../css/n/nn2sdrbun.css';
import '../../css/g/go5n_1h8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hh6tl_orr"/><path class="nclc15bex wm-a"/><path class="nn2sdrbun"/><path class="go5n_1h8p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:battery-medium-duo" /></template>
