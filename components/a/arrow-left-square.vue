<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu400dbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eu400dbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-left-square" /></template>
