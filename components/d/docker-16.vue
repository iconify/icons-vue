<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1yfnjb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p1yfnjb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:docker-16" /></template>
