<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktjh27ryf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ktjh27ryf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:c-square-fill" /></template>
