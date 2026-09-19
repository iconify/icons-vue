<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wntb91h_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wntb91h_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:electricity" /></template>
