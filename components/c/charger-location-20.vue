<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crgylcbgx.css';
import '../../css/j/j_uf38bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="crgylcbgx"/><path class="j_uf38bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-location-20" /></template>
