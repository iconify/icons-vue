<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0uedab0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0uedab0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gaze" /></template>
