<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtu0zrbrj.css';
import '../../css/o/o1kbcc50r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rtu0zrbrj"/><path class="o1kbcc50r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crimper-48" /></template>
