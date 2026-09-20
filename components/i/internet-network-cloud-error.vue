<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcrzu6bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pcrzu6bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:internet-network-cloud-error" /></template>
