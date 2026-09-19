<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urkf6-1ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urkf6-1ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-bow" /></template>
