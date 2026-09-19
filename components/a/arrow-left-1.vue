<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2-w-sber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2-w-sber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-1" /></template>
