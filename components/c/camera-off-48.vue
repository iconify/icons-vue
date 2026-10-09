<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvnxtwbjm.css';
import '../../css/a/aaaysobzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pvnxtwbjm"/><path class="aaaysobzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-off-48" /></template>
