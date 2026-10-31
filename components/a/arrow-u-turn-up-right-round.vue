<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrk0z1wmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrk0z1wmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-up-right-round" /></template>
