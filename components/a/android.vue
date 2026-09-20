<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgzr6pbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sgzr6pbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:android" /></template>
