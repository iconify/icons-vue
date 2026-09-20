<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aqzhvubby.css';
import '../../css/f/fcclfacgt.css';
import '../../css/n/ndk9d1-za.css';
import '../../css/z/zr35ecbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aqzhvubby"/><path class="fcclfacgt"/><path class="ndk9d1-za"/><path class="zr35ecbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-warning-line-duotone" /></template>
