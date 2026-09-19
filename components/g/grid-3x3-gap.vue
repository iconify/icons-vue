<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rknc7jbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rknc7jbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-3x3-gap" /></template>
