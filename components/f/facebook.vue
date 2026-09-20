<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pta4jsbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pta4jsbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:facebook" /></template>
