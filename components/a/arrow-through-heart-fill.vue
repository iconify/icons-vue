<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmz5xyl5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kmz5xyl5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-through-heart-fill" /></template>
