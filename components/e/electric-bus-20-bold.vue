<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwoyjqbns.css';
import '../../css/h/h0i-lgbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cwoyjqbns"/><path class="h0i-lgbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-bus-20-bold" /></template>
