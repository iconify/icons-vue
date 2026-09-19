<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulyr7qb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ulyr7qb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-right" /></template>
