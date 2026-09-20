<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qane4gfmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qane4gfmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airplane-enabled-remix" /></template>
