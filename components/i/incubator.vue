<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz4rlx_oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz4rlx_oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:incubator" /></template>
