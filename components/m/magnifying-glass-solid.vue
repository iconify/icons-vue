<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihtfwr4-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ihtfwr4-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magnifying-glass-solid" /></template>
