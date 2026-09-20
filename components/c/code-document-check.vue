<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy0ni9bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gy0ni9bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:code-document-check" /></template>
