<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i65vnosto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i65vnosto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:code" /></template>
