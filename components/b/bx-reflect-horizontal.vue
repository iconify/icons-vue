<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epbc514ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epbc514ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-reflect-horizontal" /></template>
