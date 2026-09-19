<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud5ss4a1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ud5ss4a1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:list-columns-reverse" /></template>
