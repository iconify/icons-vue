<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m07g8ac4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m07g8ac4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:css3" /></template>
