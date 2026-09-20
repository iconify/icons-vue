<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-09s6buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i-09s6buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:descending-number-order-remix" /></template>
