<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6vk5q15g.css';
import '../../css/r/reb4c0b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6vk5q15g"/><path class="reb4c0b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link-external-24" /></template>
