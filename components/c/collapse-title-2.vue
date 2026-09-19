<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhe4of3su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dhe4of3su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:collapse-title-2" /></template>
