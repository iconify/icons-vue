<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r06jb90lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r06jb90lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:airplane-outline" /></template>
