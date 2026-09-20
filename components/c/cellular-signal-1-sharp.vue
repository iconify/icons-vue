<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r23ehcciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r23ehcciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cellular-signal-1-sharp" /></template>
