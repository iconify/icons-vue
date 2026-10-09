<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trdnv0bir.css';
import '../../css/e/el1y2bj9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="trdnv0bir"/><path class="el1y2bj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bus-20-bold" /></template>
