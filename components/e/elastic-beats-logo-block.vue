<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzlwo8b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzlwo8b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-beats-logo-block" /></template>
