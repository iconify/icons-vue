<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9l9ao62c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9l9ao62c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-rating-20-bold" /></template>
