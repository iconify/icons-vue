<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd7bbubdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd7bbubdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lee-enfield" /></template>
