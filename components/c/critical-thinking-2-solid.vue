<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghwzcqaok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghwzcqaok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:critical-thinking-2-solid" /></template>
