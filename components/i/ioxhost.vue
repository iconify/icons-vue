<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3wsjtbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1664};
const content = `<path class="y3wsjtbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:ioxhost" /></template>
