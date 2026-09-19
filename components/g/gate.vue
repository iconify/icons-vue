<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny92bacsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ny92bacsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:gate" /></template>
