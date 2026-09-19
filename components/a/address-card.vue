<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vloihibwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="vloihibwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:address-card" /></template>
