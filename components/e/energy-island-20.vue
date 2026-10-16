<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncmcqbb8g.css';
import '../../css/i/ixw6t5b1b.css';
import '../../css/i/iu8op3j7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncmcqbb8g"/><path class="ixw6t5b1b"/><path class="iu8op3j7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-island-20" /></template>
