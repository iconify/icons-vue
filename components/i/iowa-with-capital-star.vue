<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk0bp2b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vk0bp2b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:iowa-with-capital-star" /></template>
