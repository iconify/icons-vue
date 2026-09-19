<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxnm8cc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxnm8cc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crosshair-arrow" /></template>
