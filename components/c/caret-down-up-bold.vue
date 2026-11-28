<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uas7zerge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uas7zerge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:caret-down-up-bold" /></template>
