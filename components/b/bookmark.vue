<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzm_--n7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzm_--n7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:bookmark" /></template>
