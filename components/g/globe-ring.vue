<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8d1w2iyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w8d1w2iyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:globe-ring" /></template>
