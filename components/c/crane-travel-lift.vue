<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9d6omb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d9d6omb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:crane-travel-lift" /></template>
