<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmiclo8zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qmiclo8zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-right-stipple-outer" /></template>
