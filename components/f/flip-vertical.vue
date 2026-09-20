<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv2iq-ccn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2iq-ccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flip-vertical" /></template>
