<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g90x1bbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g90x1bbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-tower" /></template>
