<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwlltrbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iwlltrbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-short" /></template>
