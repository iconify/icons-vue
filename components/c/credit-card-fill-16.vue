<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_3ysdb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_3ysdb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-fill-16" /></template>
