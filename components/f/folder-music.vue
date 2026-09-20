<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjsa2gbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjsa2gbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-music" /></template>
