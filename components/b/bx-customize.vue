<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuf3gdcam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuf3gdcam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-customize" /></template>
