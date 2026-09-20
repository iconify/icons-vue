<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3b0tachj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3b0tachj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:food-court" /></template>
