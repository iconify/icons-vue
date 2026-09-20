<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjnkxhlvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jjnkxhlvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-upload-button-1-arrow-button-download-internet-network-server-up-upload" /></template>
