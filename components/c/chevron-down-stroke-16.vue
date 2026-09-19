<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b86blp5az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b86blp5az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-down-stroke-16" /></template>
