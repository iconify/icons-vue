<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5x9eib1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5x9eib1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:gas-pump" /></template>
