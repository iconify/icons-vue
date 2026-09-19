<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8-5lw43z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8-5lw43z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-column" /></template>
