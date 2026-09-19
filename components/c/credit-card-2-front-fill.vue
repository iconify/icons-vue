<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqy0fzbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sqy0fzbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:credit-card-2-front-fill" /></template>
