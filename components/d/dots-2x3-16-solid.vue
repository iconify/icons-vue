<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6np5bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vn6np5bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-16-solid" /></template>
