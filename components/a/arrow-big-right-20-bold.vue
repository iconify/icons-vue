<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ldd46pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8ldd46pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-right-20-bold" /></template>
