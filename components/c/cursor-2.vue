<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpntzicry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hpntzicry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cursor-2" /></template>
