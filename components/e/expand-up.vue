<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbnktsb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbnktsb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:expand-up" /></template>
