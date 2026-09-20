<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zof4pzbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zof4pzbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-finger-print-scan" /></template>
