<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7_k6153t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7_k6153t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-color" /></template>
