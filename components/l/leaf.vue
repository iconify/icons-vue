<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwnj6q1-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zwnj6q1-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:leaf" /></template>
