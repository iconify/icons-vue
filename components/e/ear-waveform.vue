<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqmr_mb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqmr_mb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ear-waveform" /></template>
