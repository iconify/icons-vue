<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itjermisk.css';
import '../../css/x/xu0oo2s1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itjermisk"/><path class="xu0oo2s1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-compressor-20-bold" /></template>
