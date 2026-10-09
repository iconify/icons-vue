<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhuk8-b5y.css';
import '../../css/u/u8bmg4bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhuk8-b5y"/><path class="u8bmg4bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:deforestation-20-bold" /></template>
