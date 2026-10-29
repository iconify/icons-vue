<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6mo-8bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6mo-8bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:audio-waveform-solid" /></template>
