<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy19t-b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jy19t-b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:belt-buckles" /></template>
