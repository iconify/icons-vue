<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lik4byo7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lik4byo7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:component-20-bold" /></template>
