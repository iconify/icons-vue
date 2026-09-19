<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtwe9kb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtwe9kb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cross-tab" /></template>
