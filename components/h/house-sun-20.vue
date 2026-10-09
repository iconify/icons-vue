<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/v/v2ahy-lpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="v2ahy-lpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-sun-20" /></template>
