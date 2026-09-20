<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d62f6o1xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d62f6o1xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-science-spark-remix" /></template>
