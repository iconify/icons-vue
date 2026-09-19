<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6p9v1bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6p9v1bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:bank-card" /></template>
