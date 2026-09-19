<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jverwsbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jverwsbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:camera-video-off" /></template>
