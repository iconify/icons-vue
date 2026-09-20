<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4x19-bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s4x19-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-photo-composition-vertical-camera-portrait-frame-vertical-composition-photography-photo" /></template>
