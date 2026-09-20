<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4x25obrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4x25obrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:binance" /></template>
