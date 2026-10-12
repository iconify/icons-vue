<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt1lx2bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt1lx2bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-2x2-stroke-20" /></template>
