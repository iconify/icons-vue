<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_p9eb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_p9eb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-d-circle" /></template>
