<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpzw4zd3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpzw4zd3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dribbble" /></template>
