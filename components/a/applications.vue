<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqnnh8bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqnnh8bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:applications" /></template>
