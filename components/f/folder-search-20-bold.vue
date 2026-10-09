<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2ghl_lxl.css';
import '../../css/z/zb-g-abte.css';
import '../../css/i/i0x2txbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2ghl_lxl"/><path class="zb-g-abte"/><path class="i0x2txbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-search-20-bold" /></template>
