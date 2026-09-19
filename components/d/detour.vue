<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8u-9nalj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8u-9nalj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:detour" /></template>
