<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ett0-9bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ett0-9bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ice-cream-1-remix" /></template>
