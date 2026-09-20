<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1erivbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h1erivbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-stop-watch-half-quarter-seconds-thirty-hour-half-measure-time-stopwatch" /></template>
