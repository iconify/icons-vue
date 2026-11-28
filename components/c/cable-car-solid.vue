<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4bq9bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4bq9bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cable-car-solid" /></template>
