<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdiyli40o.css';
import '../../css/p/pc-bfqbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdiyli40o"/><path class="pc-bfqbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:line-height-48-bold" /></template>
