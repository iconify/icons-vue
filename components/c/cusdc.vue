<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsepixbkn.css';
import '../../css/c/cgtb-8b0p.css';
import '../../css/d/djamc0beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsepixbkn"/><path class="cgtb-8b0p"/><path class="djamc0beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cusdc" /></template>
