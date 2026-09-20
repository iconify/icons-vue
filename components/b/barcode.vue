<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmcfcsbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmcfcsbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:barcode" /></template>
