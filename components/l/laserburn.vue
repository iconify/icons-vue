<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7_ez1_rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7_ez1_rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:laserburn" /></template>
