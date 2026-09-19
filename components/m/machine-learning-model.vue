<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqj-0svkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqj-0svkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:machine-learning-model" /></template>
