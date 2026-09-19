<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjxp1tlnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjxp1tlnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:barcode" /></template>
