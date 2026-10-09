<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jakp6uuvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jakp6uuvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-20-bold" /></template>
