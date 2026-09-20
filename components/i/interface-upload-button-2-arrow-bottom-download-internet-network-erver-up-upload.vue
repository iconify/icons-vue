<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sieahlmzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sieahlmzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-upload-button-2-arrow-bottom-download-internet-network-erver-up-upload" /></template>
