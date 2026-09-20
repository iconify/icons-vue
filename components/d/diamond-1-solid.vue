<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_w11wfxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_w11wfxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:diamond-1-solid" /></template>
