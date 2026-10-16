<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tluui_b4e.css';
import '../../css/t/tl_h0kbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tluui_b4e"/><path class="tl_h0kbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-gas-20-bold" /></template>
