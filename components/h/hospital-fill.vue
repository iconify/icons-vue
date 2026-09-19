<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8s2d0bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8s2d0bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hospital-fill" /></template>
