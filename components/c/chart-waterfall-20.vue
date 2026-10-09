<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aem9n2zvr.css';
import '../../css/u/ubsqc0zyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aem9n2zvr"/><path class="ubsqc0zyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-waterfall-20" /></template>
