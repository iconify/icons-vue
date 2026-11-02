<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lilp8103o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lilp8103o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-space-between-fill" /></template>
