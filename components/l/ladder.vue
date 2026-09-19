<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbcewlb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbcewlb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ladder" /></template>
