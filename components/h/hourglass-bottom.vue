<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rldsg_bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rldsg_bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hourglass-bottom" /></template>
