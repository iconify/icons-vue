<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoy0pabhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xoy0pabhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-voice-dark" /></template>
