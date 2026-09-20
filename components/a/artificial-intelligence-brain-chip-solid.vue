<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utb4tgbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="utb4tgbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:artificial-intelligence-brain-chip-solid" /></template>
