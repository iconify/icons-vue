<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrzjfp6nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yrzjfp6nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-fill-16" /></template>
