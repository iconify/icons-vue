<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8oafebxf.css';
import '../../css/r/r0ow-hbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8oafebxf"/><path class="r0ow-hbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-add" /></template>
