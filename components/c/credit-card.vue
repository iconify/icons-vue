<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc5evijpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wc5evijpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:credit-card" /></template>
