<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyo1rlb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyo1rlb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-play-multiple-outline" /></template>
