<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyal6lbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jyal6lbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magnifying-glass-remix" /></template>
