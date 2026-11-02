<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07_65tsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x07_65tsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-window-fill" /></template>
