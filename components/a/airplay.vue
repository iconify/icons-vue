<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggisaj66z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":408};
const content = `<path class="ggisaj66z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airplay" /></template>
