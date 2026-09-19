<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn8q6pbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qn8q6pbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-bar-up" /></template>
