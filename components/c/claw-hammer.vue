<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eog32eskm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eog32eskm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:claw-hammer" /></template>
