<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrlbef4-h.css';
import '../../css/y/y17nwib9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrlbef4-h"/><path class="y17nwib9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-click-select-tablet" /></template>
