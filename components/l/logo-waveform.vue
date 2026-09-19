<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndzk00itk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ndzk00itk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-waveform" /></template>
