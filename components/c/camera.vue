<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa3so01so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3so01so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:camera" /></template>
