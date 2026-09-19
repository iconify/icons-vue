<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccu9kxtji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ccu9kxtji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-in-stroke-12" /></template>
