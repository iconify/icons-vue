<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2aljf7ie.css';
import '../../css/m/mxxm6-awx.css';
import '../../css/u/uk8t_bc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o2aljf7ie"/><path class="mxxm6-awx"/><path class="uk8t_bc8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-mount-20" /></template>
