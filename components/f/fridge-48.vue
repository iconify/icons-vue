<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/batmvgb8l.css';
import '../../css/m/m8rkqbbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="batmvgb8l"/><path class="m8rkqbbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fridge-48" /></template>
