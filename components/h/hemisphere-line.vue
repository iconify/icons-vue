<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pigl6sbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pigl6sbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-line" /></template>
