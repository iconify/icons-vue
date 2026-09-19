<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm3vy_9vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zm3vy_9vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:funnel-16-solid" /></template>
