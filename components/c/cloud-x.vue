<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrdnzss1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrdnzss1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-x" /></template>
