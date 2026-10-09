<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm2q0vrkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dm2q0vrkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-off-20-bold" /></template>
