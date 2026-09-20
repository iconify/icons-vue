<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv_-1uxed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv_-1uxed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:laudspeaker-light" /></template>
