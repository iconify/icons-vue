<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9fygebyi.css';
import '../../css/p/pw602pb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e9fygebyi"/><path class="pw602pb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-cell-20-bold" /></template>
