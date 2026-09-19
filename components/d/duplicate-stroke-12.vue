<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikcfh6blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ikcfh6blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:duplicate-stroke-12" /></template>
