<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pycxs8orj.css';
import '../../css/k/kdnqzpb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="kdnqzpb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-star-48" /></template>
