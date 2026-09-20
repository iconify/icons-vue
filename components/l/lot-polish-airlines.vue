<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy0s0bcut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy0s0bcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lot-polish-airlines" /></template>
