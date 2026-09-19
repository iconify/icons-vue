<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcg7mybkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dcg7mybkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cloud-moon-rain" /></template>
