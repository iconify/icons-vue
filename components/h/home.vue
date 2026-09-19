<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w81rfccet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w81rfccet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:home" /></template>
