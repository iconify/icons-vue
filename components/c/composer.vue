<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crf4l7z4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":396,"height":512};
const content = `<path class="crf4l7z4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:composer" /></template>
