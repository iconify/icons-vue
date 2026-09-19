<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwus0ggfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vwus0ggfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:capacitor-wordmark" /></template>
