<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2fl-ght.css';
import '../../css/n/nhk0vvrvh.css';
import '../../css/s/s39uf-bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="nhk0vvrvh"/><path class="s39uf-bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-dots-20" /></template>
