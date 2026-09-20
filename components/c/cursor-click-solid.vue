<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu0z4-bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu0z4-bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cursor-click-solid" /></template>
