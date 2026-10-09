<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxtlryb9c.css';
import '../../css/c/cc-mqixje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rxtlryb9c"/><path class="cc-mqixje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-tub-20-bold" /></template>
