<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijwjpyboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijwjpyboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:caret-right" /></template>
