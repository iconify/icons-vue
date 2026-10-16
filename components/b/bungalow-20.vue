<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy4ls9blv.css';
import '../../css/t/tihnfkx5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dy4ls9blv"/><path class="tihnfkx5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bungalow-20" /></template>
