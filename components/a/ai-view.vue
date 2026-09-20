<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk5gcgism.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk5gcgism"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ai-view" /></template>
