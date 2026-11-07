<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgissgbda.css';
import '../../css/y/yh6ditbzn.css';
import '../../css/y/ycg7g-b4l.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgissgbda"/><path class="yh6ditbzn"/><path class="ycg7g-b4l"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-video-camera-bold-duotone" /></template>
