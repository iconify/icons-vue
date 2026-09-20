<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqwdx_ben.css';
import '../../css/y/y_fuh3bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mqwdx_ben"/><path class="y_fuh3bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-memory" /></template>
