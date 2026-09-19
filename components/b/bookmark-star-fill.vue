<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-fsjbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v4-fsjbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bookmark-star-fill" /></template>
