<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4feqdlxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4feqdlxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-outline" /></template>
