<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t05wrwc2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="t05wrwc2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-cursor-solid" /></template>
