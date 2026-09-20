<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwap7wbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwap7wbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:home-3-solid" /></template>
