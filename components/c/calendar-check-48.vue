<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pycxs8orj.css';
import '../../css/h/h1lfc-bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="h1lfc-bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-check-48" /></template>
