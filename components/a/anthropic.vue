<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lexjn9bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lexjn9bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:anthropic" /></template>
