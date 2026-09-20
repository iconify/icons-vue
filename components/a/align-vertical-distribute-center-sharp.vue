<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls65omslb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls65omslb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-distribute-center-sharp" /></template>
