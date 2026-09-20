<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbtsv3bus.css';
import '../../css/g/gtqcty8ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vbtsv3bus"/><path class="gtqcty8ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-video-movie-producer-director-chair" /></template>
