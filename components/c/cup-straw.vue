<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvg1_8wii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cvg1_8wii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cup-straw" /></template>
