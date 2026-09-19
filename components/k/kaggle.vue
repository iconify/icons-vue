<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3gqcf4nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j3gqcf4nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:kaggle" /></template>
