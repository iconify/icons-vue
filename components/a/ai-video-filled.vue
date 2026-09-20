<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0cyckyfs.css';
import '../../css/l/llov8mbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0cyckyfs"/><path class="llov8mbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-video-filled" /></template>
