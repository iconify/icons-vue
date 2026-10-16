<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn1dkmnqu.css';
import '../../css/t/th0-odbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mn1dkmnqu"/><path class="th0-odbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:axe-20-bold" /></template>
