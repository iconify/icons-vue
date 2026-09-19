<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2mb9ibim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2mb9ibim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:big-diamond-ring" /></template>
