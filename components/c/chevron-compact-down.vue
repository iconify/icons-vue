<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5e1o2yxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z5e1o2yxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-compact-down" /></template>
