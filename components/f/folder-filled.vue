<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swwap-bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swwap-bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-filled" /></template>
