<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q50x75u1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q50x75u1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-bar-contract" /></template>
