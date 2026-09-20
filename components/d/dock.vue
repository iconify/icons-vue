<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iait7tr8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iait7tr8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:dock" /></template>
