<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7q45q27k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7q45q27k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:ice-cream" /></template>
