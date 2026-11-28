<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtmobu58j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtmobu58j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kerning-solid" /></template>
