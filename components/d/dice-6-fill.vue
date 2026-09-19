<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-fpwoyhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s-fpwoyhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dice-6-fill" /></template>
