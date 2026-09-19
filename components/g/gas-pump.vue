<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2ne70b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2ne70b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gas-pump" /></template>
