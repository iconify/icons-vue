<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep3ee2sbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ep3ee2sbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-sunglasses-fill" /></template>
