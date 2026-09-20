<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k26jrzbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k26jrzbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:magnet" /></template>
