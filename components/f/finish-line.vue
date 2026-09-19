<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybdgcfh4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ybdgcfh4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:finish-line" /></template>
