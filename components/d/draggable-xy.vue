<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2a3-308n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2a3-308n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:draggable-xy" /></template>
