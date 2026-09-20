<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn2uc9buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hn2uc9buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:filter-outline" /></template>
