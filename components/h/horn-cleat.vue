<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8yw98b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j8yw98b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horn-cleat" /></template>
