<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6tclgh3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6tclgh3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:apple-seeds" /></template>
