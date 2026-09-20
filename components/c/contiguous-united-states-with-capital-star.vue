<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b16somc0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b16somc0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:contiguous-united-states-with-capital-star" /></template>
