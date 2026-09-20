<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tecn8zjex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tecn8zjex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:calendar-mark-solid" /></template>
