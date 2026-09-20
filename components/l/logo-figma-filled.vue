<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6-kq4cwx.css';
import '../../css/d/d3bnnkbfx.css';
import '../../css/b/b3ef9_bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6-kq4cwx"/><path class="d3bnnkbfx"/><path class="b3ef9_bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-figma-filled" /></template>
