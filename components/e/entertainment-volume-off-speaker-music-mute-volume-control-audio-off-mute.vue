<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn95nbc_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pn95nbc_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-volume-off-speaker-music-mute-volume-control-audio-off-mute" /></template>
