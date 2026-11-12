<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t39s4jb2d.css';
import '../../css/k/kvhhhz9be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t39s4jb2d"/><path class="kvhhhz9be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buy-me-a-coffee" /></template>
