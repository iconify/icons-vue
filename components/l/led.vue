<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr35tybjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dr35tybjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:led" /></template>
