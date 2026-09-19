<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rem8x4bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rem8x4bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:affiliatetheme" /></template>
