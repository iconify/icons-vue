<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4bctp2ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4bctp2ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bars-solid" /></template>
