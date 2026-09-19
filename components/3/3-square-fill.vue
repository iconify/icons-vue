<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwl79gqjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rwl79gqjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:3-square-fill" /></template>
