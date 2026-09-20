<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikdx8cccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ikdx8cccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beanie-solid" /></template>
