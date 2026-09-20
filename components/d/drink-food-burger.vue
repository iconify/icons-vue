<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8u6-brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bq8u6-brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:drink-food-burger" /></template>
