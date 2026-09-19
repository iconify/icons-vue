<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-3jwb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wg-3jwb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-121" /></template>
