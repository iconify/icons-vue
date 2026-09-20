<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjh-x9b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fjh-x9b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:at-in-square" /></template>
