<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv2b_yb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2b_yb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-remove-outline" /></template>
