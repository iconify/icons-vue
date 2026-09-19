<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sayb-0bmx.css';
import '../../css/i/ircx_pb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sayb-0bmx"/><path class="ircx_pb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:airplay-filled" /></template>
