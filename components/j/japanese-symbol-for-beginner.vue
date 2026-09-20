<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd83ysbnr.css';
import '../../css/t/t58dp5a-u.css';
import '../../css/y/y_g4h7d1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bd83ysbnr"/><path class="t58dp5a-u"/><path class="y_g4h7d1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:japanese-symbol-for-beginner" /></template>
