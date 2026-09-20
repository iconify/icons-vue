<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e26w32bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e26w32bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bluetooth" /></template>
