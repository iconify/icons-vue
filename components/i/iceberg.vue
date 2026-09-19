<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwp1bibiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwp1bibiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:iceberg" /></template>
