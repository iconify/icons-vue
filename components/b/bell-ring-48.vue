<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4vq0qbju.css';
import '../../css/y/yxy7ambyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4vq0qbju"/><path class="yxy7ambyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-ring-48" /></template>
