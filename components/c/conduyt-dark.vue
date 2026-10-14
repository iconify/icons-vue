<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppkq4dlxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppkq4dlxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduyt-dark" /></template>
