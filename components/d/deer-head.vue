<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snx1k3x0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snx1k3x0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:deer-head" /></template>
