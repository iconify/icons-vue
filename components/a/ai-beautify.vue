<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxqulz4gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxqulz4gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-beautify" /></template>
