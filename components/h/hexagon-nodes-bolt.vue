<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbw3xobnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cbw3xobnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hexagon-nodes-bolt" /></template>
