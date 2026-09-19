<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny8h4776m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ny8h4776m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:crow" /></template>
