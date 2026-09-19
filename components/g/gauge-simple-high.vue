<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvq7acur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxvq7acur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gauge-simple-high" /></template>
