<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi-r0bcdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pi-r0bcdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-0-percent" /></template>
