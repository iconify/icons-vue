<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt6cbni-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qt6cbni-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lowrise-building-beside-lollipop-tree-on-ground" /></template>
