<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d70kyjb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d70kyjb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:badge-wc-fill" /></template>
