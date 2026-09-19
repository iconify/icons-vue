<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-j-sbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cu-j-sbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hedjet-white-crown" /></template>
