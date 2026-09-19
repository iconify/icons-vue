<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iub6988rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iub6988rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dot-circle" /></template>
