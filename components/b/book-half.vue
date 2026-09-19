<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtzf6db9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dtzf6db9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:book-half" /></template>
