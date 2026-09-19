<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krxyf-sfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krxyf-sfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-range-fill" /></template>
