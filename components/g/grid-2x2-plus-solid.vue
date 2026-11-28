<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox8_lzbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox8_lzbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-2x2-plus-solid" /></template>
