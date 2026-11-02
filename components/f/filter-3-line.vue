<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di9mx7u9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di9mx7u9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-3-line" /></template>
