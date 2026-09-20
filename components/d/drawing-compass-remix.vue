<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nny353msn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nny353msn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:drawing-compass-remix" /></template>
