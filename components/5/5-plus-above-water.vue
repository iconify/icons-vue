<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xih3-epmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xih3-epmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:5-plus-above-water" /></template>
