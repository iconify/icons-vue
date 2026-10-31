<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjp6pgx3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjp6pgx3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-fill-round" /></template>
