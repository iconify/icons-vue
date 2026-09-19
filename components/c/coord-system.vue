<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3c7zwbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h3c7zwbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:coord-system" /></template>
