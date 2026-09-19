<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcj3c8bij.css';
import '../../css/w/w5w3u0b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kcj3c8bij"/><path class="w5w3u0b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-nutrition-outline" /></template>
