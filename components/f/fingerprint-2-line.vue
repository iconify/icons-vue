<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qet681b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qet681b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fingerprint-2-line" /></template>
