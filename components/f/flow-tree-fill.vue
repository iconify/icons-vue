<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpc22hbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpc22hbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-tree-fill" /></template>
