<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9j4y2v-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q9j4y2v-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-chip-1-solid" /></template>
