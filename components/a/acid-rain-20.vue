<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhj96-tym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uhj96-tym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acid-rain-20" /></template>
