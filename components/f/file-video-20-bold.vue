<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iccsyvk3j.css';
import '../../css/y/y9tcibr9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="y9tcibr9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-video-20-bold" /></template>
