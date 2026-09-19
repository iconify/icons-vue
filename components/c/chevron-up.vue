<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg-uzcb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg-uzcb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:chevron-up" /></template>
