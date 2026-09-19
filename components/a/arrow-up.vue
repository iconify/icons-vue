<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4l4ob-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zv4l4ob-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-up" /></template>
