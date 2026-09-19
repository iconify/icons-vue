<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw8l6dbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sw8l6dbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hanger" /></template>
