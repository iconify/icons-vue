<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkff7l4ev.css';
import '../../css/s/stwvedcof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rkff7l4ev"/><path class="stwvedcof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:internet-network-computer-upload" /></template>
