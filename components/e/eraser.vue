<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh4hakjtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gh4hakjtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:eraser" /></template>
