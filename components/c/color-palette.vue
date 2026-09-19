<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiynvfq8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jiynvfq8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:color-palette" /></template>
