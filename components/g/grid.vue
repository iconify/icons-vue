<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0b6ekbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="j0b6ekbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grid" /></template>
