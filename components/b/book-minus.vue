<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpng_obri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpng_obri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-minus" /></template>
