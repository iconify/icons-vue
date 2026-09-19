<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-0pfv32i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-0pfv32i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark-16-solid" /></template>
