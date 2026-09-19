<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_14azb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_14azb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-globe" /></template>
