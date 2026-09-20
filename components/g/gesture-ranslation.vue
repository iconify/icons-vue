<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gd5b7kbxt.css';
import '../../css/e/ebym6xj6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gd5b7kbxt"/><path class="ebym6xj6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-ranslation" /></template>
