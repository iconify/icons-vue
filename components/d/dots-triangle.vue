<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsr5qrqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clsr5qrqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dots-triangle" /></template>
