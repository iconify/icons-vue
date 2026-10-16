<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srmecmdfr.css';
import '../../css/d/d7nxq5b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="srmecmdfr"/><path class="d7nxq5b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-quality-20-bold" /></template>
