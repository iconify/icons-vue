<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9t99pbvc.css';
import '../../css/f/flil27bwc.css';
import '../../css/t/tb6-f1eyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9t99pbvc"/><path class="flil27bwc"/><path class="tb6-f1eyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beach-hut-20-bold" /></template>
