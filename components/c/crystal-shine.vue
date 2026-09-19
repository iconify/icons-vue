<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_cdbc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2_cdbc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystal-shine" /></template>
