<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwd5g8b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwd5g8b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location-food" /></template>
