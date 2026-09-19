<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1necl-fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y1necl-fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-down-16-solid" /></template>
