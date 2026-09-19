<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-uhadh3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-uhadh3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:diamond" /></template>
