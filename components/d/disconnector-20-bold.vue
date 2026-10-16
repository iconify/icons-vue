<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbdwctb6r.css';
import '../../css/w/w2y26nmkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cbdwctb6r"/><path class="w2y26nmkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disconnector-20-bold" /></template>
