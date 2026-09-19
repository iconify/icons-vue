<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da7ij4b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="da7ij4b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-color-text" /></template>
