<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk-i6tmrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vk-i6tmrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:camera" /></template>
