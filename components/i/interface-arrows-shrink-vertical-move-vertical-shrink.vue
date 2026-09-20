<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv60btb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zv60btb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-shrink-vertical-move-vertical-shrink" /></template>
