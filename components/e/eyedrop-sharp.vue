<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv9bggb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zv9bggb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eyedrop-sharp" /></template>
