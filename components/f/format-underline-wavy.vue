<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-479s9ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-479s9ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-underline-wavy" /></template>
