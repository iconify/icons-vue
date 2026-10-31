<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu4c7ydtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu4c7ydtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:label-bulk-round" /></template>
