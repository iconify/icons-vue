<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffnde8cke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffnde8cke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-lightning-48-bold" /></template>
