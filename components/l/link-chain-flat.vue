<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8yyz4_qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k8yyz4_qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:link-chain-flat" /></template>
