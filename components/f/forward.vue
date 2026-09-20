<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yubsp6bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yubsp6bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:forward" /></template>
