<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mb-rctu0w.css';
import '../../css/k/ki-z3s3do.css';
import '../../css/y/y2r41vbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mb-rctu0w"/><path class="ki-z3s3do"/><path class="y2r41vbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:invoice-04" /></template>
