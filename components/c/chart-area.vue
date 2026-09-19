<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg5z9hj3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gg5z9hj3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chart-area" /></template>
