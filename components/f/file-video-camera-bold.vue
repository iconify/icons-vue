<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8q5j9dzg.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8q5j9dzg"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-video-camera-bold" /></template>
