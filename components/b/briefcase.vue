<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmcc-y1ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmcc-y1ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:briefcase" /></template>
