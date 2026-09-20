<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggr-kcw4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggr-kcw4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:donut-solid" /></template>
