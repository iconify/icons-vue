<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0g6m1bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0g6m1bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location-hotel" /></template>
