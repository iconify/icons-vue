<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb-fub50j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wb-fub50j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airport-plane-transit-remix" /></template>
