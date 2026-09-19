<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zns64tv3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zns64tv3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:desert-eagle" /></template>
