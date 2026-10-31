<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_57np6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_57np6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-large-bulk-round" /></template>
