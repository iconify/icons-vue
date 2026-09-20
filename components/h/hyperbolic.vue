<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rakq8lbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rakq8lbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hyperbolic" /></template>
