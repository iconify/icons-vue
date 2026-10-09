<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjz7p6x4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tjz7p6x4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:couple-20" /></template>
