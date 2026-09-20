<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0b-ftb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0b-ftb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:computer-chip-1-remix" /></template>
