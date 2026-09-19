<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsf0-2bjx.css';
import '../../css/b/bouxdeh8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xsf0-2bjx"/><path class="bouxdeh8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:accessibility-outline" /></template>
