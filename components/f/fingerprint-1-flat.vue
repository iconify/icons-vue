<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr9_-zvzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wr9_-zvzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:fingerprint-1-flat" /></template>
