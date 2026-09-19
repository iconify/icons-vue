<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j36ff-b8d.css';
import '../../css/q/qeixe-bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j36ff-b8d"/><path class="qeixe-bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:java-record" /></template>
