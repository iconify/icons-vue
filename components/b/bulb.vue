<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgibdk_pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgibdk_pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bulb" /></template>
