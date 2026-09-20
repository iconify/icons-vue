<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llm2n6bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llm2n6bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-refresh-outline" /></template>
