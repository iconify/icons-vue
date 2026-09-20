<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pecbn_bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="pecbn_bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-up-left" /></template>
