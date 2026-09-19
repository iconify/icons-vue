<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-2oxgbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-2oxgbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-heart-fill" /></template>
