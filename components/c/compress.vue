<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-fia57dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d-fia57dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:compress" /></template>
