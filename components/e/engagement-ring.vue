<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s357eiyeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s357eiyeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:engagement-ring" /></template>
