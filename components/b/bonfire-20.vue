<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvohhboi.css';
import '../../css/w/wrlhybbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tjvohhboi"/><path class="wrlhybbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bonfire-20" /></template>
