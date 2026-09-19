<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2yqzbbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i2yqzbbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-heart-fill" /></template>
