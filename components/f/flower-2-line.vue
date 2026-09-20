<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bql6m9uhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bql6m9uhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:flower-2-line" /></template>
