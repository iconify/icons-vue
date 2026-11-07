<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3xgtgbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xgtgbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-down" /></template>
