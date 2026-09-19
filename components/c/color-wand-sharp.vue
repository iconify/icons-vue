<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evvfitddh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evvfitddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-wand-sharp" /></template>
