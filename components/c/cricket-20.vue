<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkayohb4a.css';
import '../../css/n/n76vy6bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkayohb4a"/><path class="n76vy6bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cricket-20" /></template>
