<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytfd0j2fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytfd0j2fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:camera-heart" /></template>
