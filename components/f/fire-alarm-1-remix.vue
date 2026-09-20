<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i09db8b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i09db8b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fire-alarm-1-remix" /></template>
