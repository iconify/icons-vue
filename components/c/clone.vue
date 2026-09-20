<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pixwip90b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pixwip90b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:clone" /></template>
