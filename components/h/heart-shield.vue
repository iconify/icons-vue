<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3wz1bbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3wz1bbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-shield" /></template>
