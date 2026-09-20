<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzzdz3wvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzzdz3wvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ieee" /></template>
