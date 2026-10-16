<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2zvukrgy.css';
import '../../css/n/nxke65bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2zvukrgy"/><path class="nxke65bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glacier-20-bold" /></template>
