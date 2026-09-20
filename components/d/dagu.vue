<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va_1o5bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="va_1o5bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagu" /></template>
