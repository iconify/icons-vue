<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa0_5kb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pa0_5kb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:building-fill" /></template>
