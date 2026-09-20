<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hll991hcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hll991hcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:anchor-remix" /></template>
