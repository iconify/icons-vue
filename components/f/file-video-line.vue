<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov64d2bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov64d2bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-video-line" /></template>
