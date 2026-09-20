<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa3i2xbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wa3i2xbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-minimalistic-bold" /></template>
