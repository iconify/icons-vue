<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pat2y4biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pat2y4biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:home-thatched" /></template>
