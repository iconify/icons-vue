<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xriuw52tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xriuw52tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:climb" /></template>
