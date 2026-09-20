<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlrvlsb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nlrvlsb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:acmdl-square" /></template>
