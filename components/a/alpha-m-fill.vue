<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0huf36pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="r0huf36pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-m-fill" /></template>
