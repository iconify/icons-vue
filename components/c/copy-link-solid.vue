<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln3utrbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln3utrbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:copy-link-solid" /></template>
