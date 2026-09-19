<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0eda4_8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0eda4_8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hourglass-sharp" /></template>
