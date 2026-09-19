<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmsdd661s.css';
import '../../css/k/ktlmm7bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmsdd661s"/><path class="ktlmm7bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-building" /></template>
