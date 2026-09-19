<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9_5x1_iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9_5x1_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:c-circle-fill" /></template>
