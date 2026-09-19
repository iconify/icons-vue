<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1xq18ehc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1xq18ehc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:computer-fan" /></template>
