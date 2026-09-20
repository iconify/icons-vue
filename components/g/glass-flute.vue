<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhwraxbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhwraxbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-flute" /></template>
