<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6je0znxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6je0znxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:internet-protocol" /></template>
