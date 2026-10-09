<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut-z-5uyn.css';
import '../../css/f/fh5ya8rmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ut-z-5uyn"/><path class="fh5ya8rmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bowling-48" /></template>
