<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r821r0b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r821r0b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:envelope" /></template>
