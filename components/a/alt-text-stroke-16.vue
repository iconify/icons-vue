<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko5onlbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ko5onlbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-stroke-16" /></template>
