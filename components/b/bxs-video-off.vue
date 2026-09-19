<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crw1gbcbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crw1gbcbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-video-off" /></template>
