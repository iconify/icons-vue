<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b923_bb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b923_bb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:balaclava" /></template>
