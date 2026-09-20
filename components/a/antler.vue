<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzprjac0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hzprjac0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:antler" /></template>
