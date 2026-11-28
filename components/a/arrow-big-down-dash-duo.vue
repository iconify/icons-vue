<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws9c0dbot.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oqw9z-byp.css';
import '../../css/u/us6x24bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ws9c0dbot"/><g class="dt0cm9dhy primary"><path class="oqw9z-byp"/><path class="us6x24bsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-down-dash-duo" /></template>
