<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brydu94pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brydu94pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:emerald-necklace" /></template>
