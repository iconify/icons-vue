<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in3z5o4jq.css';
import '../../css/e/etos_bc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="in3z5o4jq"/><path class="etos_bc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:biome-wordmark" /></template>
