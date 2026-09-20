<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjmi-ivvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjmi-ivvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-text-input-area-1" /></template>
