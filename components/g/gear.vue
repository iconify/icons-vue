<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb_0-umdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb_0-umdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:gear" /></template>
