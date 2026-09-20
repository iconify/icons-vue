<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shfcvx8wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="shfcvx8wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:jump-down" /></template>
