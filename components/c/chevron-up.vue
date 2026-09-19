<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8ygnl_-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1280};
const content = `<path class="e8ygnl_-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-up" /></template>
