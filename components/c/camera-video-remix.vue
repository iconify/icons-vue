<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iirj12wnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iirj12wnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:camera-video-remix" /></template>
