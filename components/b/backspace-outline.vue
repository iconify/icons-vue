<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1mehsijf.css';
import '../../css/q/qqdio8bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k1mehsijf"/><path class="qqdio8bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:backspace-outline" /></template>
