<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmbmp5byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmbmp5byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:equal-20-bold" /></template>
