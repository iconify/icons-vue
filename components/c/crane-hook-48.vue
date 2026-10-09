<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo1gldv5s.css';
import '../../css/f/fjkjw2x4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo1gldv5s"/><path class="fjkjw2x4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crane-hook-48" /></template>
