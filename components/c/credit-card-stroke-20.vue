<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhl4eccuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rhl4eccuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-stroke-20" /></template>
