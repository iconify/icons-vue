<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ahhc2jbks.css';
import '../../css/r/rw0tps2ji.css';
import '../../css/f/fs4i84bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ahhc2jbks"/><path class="rw0tps2ji"/><path class="fs4i84bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:log-in" /></template>
