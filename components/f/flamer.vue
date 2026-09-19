<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5olcob6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5olcob6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flamer" /></template>
