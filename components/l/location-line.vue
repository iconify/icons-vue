<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jknbwyp-h.css';
import '../../css/l/lzloo5hnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jknbwyp-h"/><path class="lzloo5hnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-line" /></template>
