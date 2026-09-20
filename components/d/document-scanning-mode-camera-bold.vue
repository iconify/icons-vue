<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfpj7sbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfpj7sbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:document-scanning-mode-camera-bold" /></template>
