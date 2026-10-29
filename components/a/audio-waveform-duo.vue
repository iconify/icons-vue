<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxql_cb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxql_cb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:audio-waveform-duo" /></template>
