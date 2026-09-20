<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc_rbobbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hc_rbobbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-solid" /></template>
