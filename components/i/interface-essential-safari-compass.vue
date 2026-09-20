<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi0smr2nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mi0smr2nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-safari-compass" /></template>
