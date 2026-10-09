<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4d61mpoq.css';
import '../../css/l/l0042n2sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4d61mpoq"/><path class="l0042n2sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuse-20-bold" /></template>
