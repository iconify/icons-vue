<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur0oo-1qr.css';
import '../../css/q/quz16u80s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur0oo-1qr"/><path class="quz16u80s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:backpack-48-bold" /></template>
