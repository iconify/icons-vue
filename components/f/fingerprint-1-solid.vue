<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6bz4cbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p6bz4cbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fingerprint-1-solid" /></template>
