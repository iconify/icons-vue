<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uko8rh9_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uko8rh9_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:magnifying-glass" /></template>
