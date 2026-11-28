<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7xarkbwg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/detamnbsk.css';
import '../../css/h/hw4x0eb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7xarkbwg secondary"/><g class="dt0cm9dhy primary"><path class="detamnbsk"/><path class="hw4x0eb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clover-duo" /></template>
