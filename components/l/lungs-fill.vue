<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5c9r5brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w5c9r5brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lungs-fill" /></template>
