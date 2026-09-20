<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5yr23bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s5yr23bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:drink-food-food" /></template>
