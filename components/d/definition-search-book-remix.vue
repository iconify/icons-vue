<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk68a97yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk68a97yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:definition-search-book-remix" /></template>
