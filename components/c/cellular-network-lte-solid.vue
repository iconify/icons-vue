<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqsm_1b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aqsm_1b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-lte-solid" /></template>
