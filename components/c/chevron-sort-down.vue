<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efn51qbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="efn51qbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-sort-down" /></template>
