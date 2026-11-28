<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnwtwpqmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwtwpqmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-nand-solid" /></template>
