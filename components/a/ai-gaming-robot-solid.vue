<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et40e2byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="et40e2byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-gaming-robot-solid" /></template>
