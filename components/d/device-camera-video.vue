<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n359shbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n359shbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-camera-video" /></template>
