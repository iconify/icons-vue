<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsp2f4jtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsp2f4jtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-hubble-dark" /></template>
