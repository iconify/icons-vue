<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2x0_ablt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r2x0_ablt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:curly-brackets" /></template>
