<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1gnxjbff.css';
import '../../css/d/d7kvl-bfh.css';
import '../../css/y/ymywn-lwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1gnxjbff"/><path class="d7kvl-bfh"/><path class="ymywn-lwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-search" /></template>
