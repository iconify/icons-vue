<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czxxxcbar.css';
import '../../css/g/ga-ypktcu.css';
import '../../css/e/em6--xtxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czxxxcbar"/><path class="ga-ypktcu"/><path class="em6--xtxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airport-20-bold" /></template>
