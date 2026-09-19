<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd51n3b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pd51n3b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filter-square-fill" /></template>
