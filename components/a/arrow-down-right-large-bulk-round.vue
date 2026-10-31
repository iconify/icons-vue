<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it0rrpb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it0rrpb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-large-bulk-round" /></template>
