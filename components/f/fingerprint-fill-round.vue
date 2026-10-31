<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo-3fcnkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo-3fcnkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fingerprint-fill-round" /></template>
