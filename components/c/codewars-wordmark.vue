<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upq7_ybsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="upq7_ybsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codewars-wordmark" /></template>
