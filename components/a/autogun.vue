<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oor0fndvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oor0fndvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:autogun" /></template>
