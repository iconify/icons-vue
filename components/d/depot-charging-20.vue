<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no8_0h65g.css';
import '../../css/e/eyio-_5vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="no8_0h65g"/><path class="eyio-_5vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:depot-charging-20" /></template>
