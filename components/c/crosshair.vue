<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njcx8jb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njcx8jb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:crosshair" /></template>
