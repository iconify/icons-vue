<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbds7eckz.css';
import '../../css/p/p6kfs-93h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xbds7eckz"/><path class="p6kfs-93h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apacheignite-wordmark" /></template>
