<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei_1tabmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ei_1tabmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:grab" /></template>
