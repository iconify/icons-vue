<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6d9jv8kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j6d9jv8kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:align-right-16" /></template>
