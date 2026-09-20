<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygkp9caur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ygkp9caur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-rupee-solid" /></template>
