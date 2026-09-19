<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-wxe198h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-wxe198h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:growth" /></template>
