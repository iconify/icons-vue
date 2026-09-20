<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdo_mb58d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zdo_mb58d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:key-and-arrow-right-above-arrow-left" /></template>
