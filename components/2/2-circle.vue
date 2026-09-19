<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_cn00-dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q_cn00-dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:2-circle" /></template>
