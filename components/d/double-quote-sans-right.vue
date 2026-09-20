<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naa-2hjrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="naa-2hjrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:double-quote-sans-right" /></template>
