<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv-n-8s8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nv-n-8s8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:digital-totem" /></template>
