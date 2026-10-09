<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq5ig7bzi.css';
import '../../css/z/zt4ibv4ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jq5ig7bzi"/><path class="zt4ibv4ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desert-20-bold" /></template>
