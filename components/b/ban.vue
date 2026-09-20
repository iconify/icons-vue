<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e24ytlbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e24ytlbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:ban" /></template>
