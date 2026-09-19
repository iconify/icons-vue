<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9pq2-b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b9pq2-b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-chimney-window" /></template>
