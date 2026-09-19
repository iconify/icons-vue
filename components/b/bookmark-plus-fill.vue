<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6kk1bc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6kk1bc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bookmark-plus-fill" /></template>
