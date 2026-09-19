<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdun30biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdun30biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:finger-print-outline" /></template>
