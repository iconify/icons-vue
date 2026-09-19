<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihekl3wxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihekl3wxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-reflect-vertical" /></template>
