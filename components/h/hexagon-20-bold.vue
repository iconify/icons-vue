<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsioiwbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsioiwbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hexagon-20-bold" /></template>
