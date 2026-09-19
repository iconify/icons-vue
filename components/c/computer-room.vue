<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ta8jbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ta8jbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:computer-room" /></template>
