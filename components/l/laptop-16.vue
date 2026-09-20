<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3z9inily.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s3z9inily"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:laptop-16" /></template>
