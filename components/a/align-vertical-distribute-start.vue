<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3_iqvbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3_iqvbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-distribute-start" /></template>
