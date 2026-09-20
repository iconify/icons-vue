<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-c-fz4gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-c-fz4gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-play" /></template>
