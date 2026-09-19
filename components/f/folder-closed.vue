<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy3be5beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy3be5beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:folder-closed" /></template>
