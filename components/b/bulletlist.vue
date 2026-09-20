<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epi0c1bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epi0c1bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bulletlist" /></template>
