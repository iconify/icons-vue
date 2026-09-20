<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaeolubqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iaeolubqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-skate" /></template>
