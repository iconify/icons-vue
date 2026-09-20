<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amvtn4bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amvtn4bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-line" /></template>
