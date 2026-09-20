<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg_1uzbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fg_1uzbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-and-arrow-right-above-arrow-left" /></template>
