<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-1pkbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wm-1pkbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:counterclockwise" /></template>
