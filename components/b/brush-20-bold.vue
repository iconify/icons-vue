<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvp9p07ws.css';
import '../../css/n/n3lls7b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rvp9p07ws"/><path class="n3lls7b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brush-20-bold" /></template>
