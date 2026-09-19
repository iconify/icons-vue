<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv1bekots.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv1bekots"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glass-heart" /></template>
