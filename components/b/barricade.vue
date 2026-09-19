<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnkb_wbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vnkb_wbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barricade" /></template>
