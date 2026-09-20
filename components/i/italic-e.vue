<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igi0b0bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igi0b0bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-e" /></template>
