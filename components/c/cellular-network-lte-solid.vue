<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr9hgly8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cr9hgly8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cellular-network-lte-solid" /></template>
