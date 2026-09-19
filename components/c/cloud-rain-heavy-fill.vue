<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4pf3kmmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w4pf3kmmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-rain-heavy-fill" /></template>
