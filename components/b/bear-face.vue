<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8g-wib6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8g-wib6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:bear-face" /></template>
