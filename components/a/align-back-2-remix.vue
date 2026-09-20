<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc6ecmbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc6ecmbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:align-back-2-remix" /></template>
