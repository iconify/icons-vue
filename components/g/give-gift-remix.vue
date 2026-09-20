<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x03w4o6-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x03w4o6-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:give-gift-remix" /></template>
