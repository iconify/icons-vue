<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5-o9ybxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="f5-o9ybxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:forward" /></template>
