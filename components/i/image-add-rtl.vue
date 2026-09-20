<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdylx-b6p.css';
import '../../css/s/skx7sybde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdylx-b6p"/><path class="skx7sybde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-add-rtl" /></template>
