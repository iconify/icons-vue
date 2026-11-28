<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8sggb0m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pxvp_ztez.css';
import '../../css/i/ij7qju6sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8sggb0m secondary"/><g class="dt0cm9dhy primary"><path class="pxvp_ztez"/><circle class="ij7qju6sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flower-duo" /></template>
