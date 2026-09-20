<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywgza-9bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ywgza-9bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:4-plus-above-water" /></template>
