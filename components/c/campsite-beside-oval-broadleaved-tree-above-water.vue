<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7_5l5l3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c7_5l5l3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-beside-oval-broadleaved-tree-above-water" /></template>
