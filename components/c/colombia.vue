<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1xs4ji-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1xs4ji-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:colombia" /></template>
