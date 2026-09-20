<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg7rvpbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pg7rvpbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bluetooth-solid" /></template>
