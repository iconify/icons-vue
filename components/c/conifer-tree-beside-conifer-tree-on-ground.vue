<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir2pffbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ir2pffbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-beside-conifer-tree-on-ground" /></template>
