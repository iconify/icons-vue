<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh2ydkb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh2ydkb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-dropup-circle" /></template>
