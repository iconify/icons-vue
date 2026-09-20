<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe10_4owo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oe10_4owo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:image-solid" /></template>
