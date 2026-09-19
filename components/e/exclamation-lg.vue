<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flln8sb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="flln8sb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation-lg" /></template>
