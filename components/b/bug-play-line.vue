<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgk77_x6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgk77_x6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bug-play-line" /></template>
