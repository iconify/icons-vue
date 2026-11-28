<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ein_ggb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ein_ggb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bottle-check" /></template>
