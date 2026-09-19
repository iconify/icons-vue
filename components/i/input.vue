<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgb1p3bxd.css';
import '../../css/r/rlnza7pox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgb1p3bxd"/><path class="rlnza7pox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:input" /></template>
