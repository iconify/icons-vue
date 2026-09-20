<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2clycb-g.css';
import '../../css/w/wpypx_dri.css';
import '../../css/f/fdhg8oy1z.css';
import '../../css/g/gsdiynbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2clycb-g"/><path class="wpypx_dri"/><path clip-rule="evenodd" class="fdhg8oy1z"/><path class="gsdiynbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:items-tree-24" /></template>
