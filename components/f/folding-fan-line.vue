<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsut6wb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsut6wb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folding-fan-line" /></template>
