<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6n4bfy8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6n4bfy8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:book-open-16-solid" /></template>
