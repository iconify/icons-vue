<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu2_20dau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="xu2_20dau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:filtering" /></template>
