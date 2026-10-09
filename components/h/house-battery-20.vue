<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/u/uu578rb0y.css';
import '../../css/a/abch41bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="uu578rb0y"/><path class="abch41bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-battery-20" /></template>
