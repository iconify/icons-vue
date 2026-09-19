<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d09b06_ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d09b06_ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hat" /></template>
