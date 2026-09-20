<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7p48actu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m7p48actu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-three-clock-fifteen-three-quarter-minutes-time-hour" /></template>
