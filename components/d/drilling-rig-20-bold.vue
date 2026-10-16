<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tly2nbbsq.css';
import '../../css/e/eoifswn5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tly2nbbsq"/><path class="eoifswn5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drilling-rig-20-bold" /></template>
