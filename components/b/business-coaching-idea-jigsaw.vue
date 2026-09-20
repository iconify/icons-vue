<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhx33-fu.css';
import '../../css/i/iy9nx5bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhx33-fu"/><path class="iy9nx5bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-coaching-idea-jigsaw" /></template>
