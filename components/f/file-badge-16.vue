<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yetj49bbr.css';
import '../../css/c/cad3x_r9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yetj49bbr"/><path class="cad3x_r9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-badge-16" /></template>
