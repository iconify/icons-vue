<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgk369bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wgk369bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checker-medium" /></template>
