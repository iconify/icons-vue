<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecvi1i71l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecvi1i71l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-open" /></template>
