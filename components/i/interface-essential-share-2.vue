<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n19_18s0x.css';
import '../../css/e/ee3e3_fof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n19_18s0x"/><path class="ee3e3_fof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-share-2" /></template>
