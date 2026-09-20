<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2jz3n1-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2jz3n1-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bluetooth" /></template>
