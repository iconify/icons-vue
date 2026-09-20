<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtlu3wbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xtlu3wbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:fire" /></template>
