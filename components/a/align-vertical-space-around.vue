<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe9-bnb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe9-bnb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-space-around" /></template>
