<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdxjo73ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdxjo73ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:long-antennae-bug" /></template>
