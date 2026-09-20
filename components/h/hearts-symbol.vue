<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz2eh4s9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kz2eh4s9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hearts-symbol" /></template>
