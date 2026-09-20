<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_xknqb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d_xknqb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-volume-up-volume-speaker-up-control-music-plus-add-audio-increase" /></template>
