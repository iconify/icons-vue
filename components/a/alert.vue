<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulydlxb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ulydlxb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:alert" /></template>
