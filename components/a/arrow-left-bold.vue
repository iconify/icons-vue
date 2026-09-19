<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erpo6qb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="erpo6qb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:arrow-left-bold" /></template>
