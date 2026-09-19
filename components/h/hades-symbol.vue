<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otcpxlqtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otcpxlqtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hades-symbol" /></template>
