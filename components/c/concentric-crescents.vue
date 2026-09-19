<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv4kqqbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv4kqqbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:concentric-crescents" /></template>
