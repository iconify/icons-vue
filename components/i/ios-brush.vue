<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5792dbmu.css';
import '../../css/l/l80m0bc3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5792dbmu"/><path class="l80m0bc3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-brush" /></template>
