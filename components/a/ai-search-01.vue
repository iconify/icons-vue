<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-t86rtqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-t86rtqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-search-01" /></template>
