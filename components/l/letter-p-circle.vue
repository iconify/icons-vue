<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2j1l3yzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2j1l3yzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-p-circle" /></template>
