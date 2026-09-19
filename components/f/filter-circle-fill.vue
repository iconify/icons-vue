<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co36qraxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="co36qraxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filter-circle-fill" /></template>
