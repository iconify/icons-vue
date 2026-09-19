<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5enlybph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d5enlybph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:basket2-fill" /></template>
