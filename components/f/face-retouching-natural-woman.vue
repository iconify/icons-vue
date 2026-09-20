<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j13k_rbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j13k_rbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-retouching-natural-woman" /></template>
