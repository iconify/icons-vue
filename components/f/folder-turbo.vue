<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kvzedtd8y.css';
import '../../css/i/i3yjklbnq.css';
import '../../css/w/wzup-8xfj.css';
import '../../css/j/jfemo-btz.css';
import '../../css/q/q434f9b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="kvzedtd8y"/><circle class="i3yjklbnq"/><path class="wzup-8xfj"/><path class="jfemo-btz"/><path class="q434f9b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-turbo" /></template>
