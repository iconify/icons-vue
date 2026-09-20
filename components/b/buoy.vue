<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpqcn6bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zbpqcn6bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:buoy" /></template>
