<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ac4w-4l8x.css';
import '../../css/c/crugkkdfe.css';
import '../../css/f/ffmjv2bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ac4w-4l8x"/><path class="crugkkdfe wm-k"/><path class="ffmjv2bzj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-koala-sketch" /></template>
