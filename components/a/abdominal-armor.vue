<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8m8pbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qj8m8pbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abdominal-armor" /></template>
