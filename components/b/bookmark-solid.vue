<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0crakb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m0crakb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:bookmark-solid" /></template>
