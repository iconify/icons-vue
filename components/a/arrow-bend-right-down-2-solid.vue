<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfrnmabrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfrnmabrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-bend-right-down-2-solid" /></template>
