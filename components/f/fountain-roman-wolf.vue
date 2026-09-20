<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-zwsvbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-zwsvbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:fountain-roman-wolf" /></template>
