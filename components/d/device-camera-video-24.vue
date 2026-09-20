<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymj9h20wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymj9h20wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-camera-video-24" /></template>
