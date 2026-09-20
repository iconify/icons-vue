<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoym41box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoym41box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-cursor-move-remix" /></template>
