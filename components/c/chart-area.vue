<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5m8x1bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x5m8x1bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chart-area" /></template>
