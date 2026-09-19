<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q92jog0yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q92jog0yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:credit-card-2-back-fill" /></template>
