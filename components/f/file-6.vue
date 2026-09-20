<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5pgxohry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5pgxohry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-6" /></template>
