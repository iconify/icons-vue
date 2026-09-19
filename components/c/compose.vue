<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wezx3bbsv.css';
import '../../css/j/j14wpibjz.css';
import '../../css/w/wv5glxoac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wezx3bbsv"/><path class="j14wpibjz"/><path class="wv5glxoac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:compose" /></template>
