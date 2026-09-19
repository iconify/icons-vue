<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzjqs1bbd.css';
import '../../css/k/kx75bricy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wzjqs1bbd"/><path class="kx75bricy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:file-tray-outline" /></template>
