<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcwzkjb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcwzkjb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ambulance" /></template>
