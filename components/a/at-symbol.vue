<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9_teob1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9_teob1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:at-symbol" /></template>
